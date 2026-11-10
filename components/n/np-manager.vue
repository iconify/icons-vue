<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pumcb2brn"/><path class="d_6eeib-x"/><path class="ac0vrgban"/><path class="n3s3elbkd"/><path class="z4ajmgfcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:np-manager" /></template>
<style>
.ac0vrgban {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.568 35.283V24.436a5.49 5.49 0 0 0-5.5-5.5h-.095a5.49 5.49 0 0 0-5.5 5.48v10.867");
}

.d_6eeib-x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.203 16.874h7.681c1.663 0 3 1.338 3 3v19.527c0 1.662-1.337 3-3 3H7.111c-1.662 0-3-1.338-3-3V15.649c0-1.662 1.338-3 3-3h18.366c1.03 0 1.985.38 2.676 1.005l2.413 2.183c.72.65 1.517 1.037 2.637 1.037M9.984 9.247h28.04m1.966 4.752H28.752");
}

.n3s3elbkd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.626 20.233a5.557 5.557 0 0 1 9.125 4.26a5.557 5.557 0 0 1-7.187 5.313m-2.323-1.407a5.55 5.55 0 0 1-1.062-6.301m14.38 20.305c-1.792-3.44-.556-7.966 3.03-10.52c2.933-2.087 6.6-2.261 9.3-.72m-15.772 2.06l3.74 1.682m6.11-8.696l.373 4.078");
}

.pumcb2brn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.546 12.704V9.097c0-1.94 1.56-3.5 3.5-3.5h29.68c1.937 0 3.5 1.56 3.5 3.5v8.608");
}

.z4ajmgfcz {
  fill: currentColor;
  d: path("M40.594 32.329a.76.76 0 0 1-.19 1.048a.74.74 0 0 1-1.036-.149l-.008-.011a.76.76 0 0 1 .19-1.048a.74.74 0 0 1 1.035.149zm-6.3 4.486a.76.76 0 0 1-.19 1.049a.74.74 0 0 1-1.044-.16a.76.76 0 0 1 .19-1.049a.74.74 0 0 1 1.043.16");
}

</style>
