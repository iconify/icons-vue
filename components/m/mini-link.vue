<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rvxdvzbbq"/><path class="zo_npsb8h"/><path class="zidhyac_r"/><path class="zdss98b3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mini-link" /></template>
<style>
.rvxdvzbbq {
  fill: currentColor;
  d: path("M8.679 32.243a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.zdss98b3u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.636 32.533v-9.92c0-3.67 1.123-5.58 1.556-6.356m1.473 16.276v-9.92c0-3.88.683-5.619 1.279-6.522m1.75 16.442v-9.92c0-3.144.453-5.478.752-6.379m2.278 16.3v-9.922c0-3.879.144-5.125.567-6.46m2.462 16.381V16.37m3.029 14.294V16.37M37.9 32.533v-9.92c0-3.67-1.123-5.58-1.557-6.356M34.87 32.533v-9.92c0-3.88-.683-5.619-1.279-6.522m-1.75 16.442v-9.92c0-3.144-.452-5.478-.752-6.379m-2.277 16.3v-9.922c0-3.879-.144-5.125-.568-6.46");
}

.zidhyac_r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.361 29.769l.25-9.685c.06-2.257.966-4.075 4.062-4.075h23.4c3.095 0 4.002 1.818 4.06 4.075l.323 12.449");
}

.zo_npsb8h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m40.821 35.306l-5.149 6.625m5.149 0l-5.149-6.625m-27.743 0v6.625m9.795-.56c.47.384.978.56 2.117.56h.578c.94 0 1.701-.741 1.701-1.656h0c0-.915-.761-1.656-1.701-1.656h-1.155c-.94 0-1.702-.742-1.702-1.657h0c0-.915.762-1.657 1.702-1.657h.577c1.14 0 1.647.177 2.117.56m3.355-2.623v7.439c0 .69.576 1.25 1.287 1.25h.386m-3.025-6.625h2.703m6.898 4.125c0 1.38-1.152 2.5-2.574 2.5h0c-1.422 0-2.574-1.12-2.574-2.5v-1.625c0-1.38 1.152-2.5 2.574-2.5h0c1.422 0 2.574 1.12 2.574 2.5m0 4.125v-6.625M15.564 41.93v-4.125c0-1.38-1.153-2.5-2.575-2.5h0c-1.421 0-2.574 1.12-2.574 2.5m0 4.125v-6.625m3.374-19.297V6.535c0-.259.209-.467.468-.467h20.097c.259 0 .468.208.468.467v9.474");
}

</style>
