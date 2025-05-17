#🔧 How to Apply the Patch
1. Save the patch file above as maodv_misbehavior.patch.
2. Place it in the root of your NS2 source directory (e.g., ns-2.33/).
3. Apply the patch using:
   `patch -p1 < maodv_misbehavior.patch`
4. Rebuild ns2:
   `make clean && make`
