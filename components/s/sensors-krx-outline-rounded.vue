<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yb1x1x1om"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sensors-krx-outline-rounded" /></template>
<style>
.yb1x1x1om {
  fill: currentColor;
  d: path("M4.27 14.103q.27 1.018.792 1.895q.122.202.093.416t-.207.342q-.177.135-.385.06q-.207-.074-.311-.256q-.594-1.012-.923-2.158T3 12t.329-2.405t.923-2.16q.104-.183.312-.254t.384.063q.177.129.207.343t-.094.415q-.52.877-.79 1.895Q4 10.916 4 12t.27 2.103m3.759 1.868Q6.385 14.327 6.385 12t1.644-3.971T12 6.385t3.971 1.644T17.616 12t-1.645 3.971T12 17.616T8.029 15.97m7.238-.704Q16.616 13.92 16.616 12t-1.349-3.267T12 7.384t-3.267 1.35Q7.384 10.08 7.384 12t1.349 3.267T12 16.616t3.267-1.349m4.453-5.37q-.28-1.018-.8-1.895q-.124-.202-.087-.416t.213-.342q.177-.134.388-.063q.21.071.314.254q.594 1.011.923 2.16T21 12t-.329 2.402t-.923 2.158q-.104.182-.314.256t-.388-.06q-.177-.129-.213-.343t.086-.415q.522-.877.801-1.895Q20 13.085 20 12t-.28-2.103M12 12");
}

</style>
