<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0wcu-h-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:music-cast-rounded" /></template>
<style>
.p0wcu-h-n {
  fill: currentColor;
  d: path("M12.089 18.123q-.877-.877-.877-2.123t.877-2.123T14.212 13q.575 0 1.091.205t.909.614V5.5q0-.348.23-.578t.577-.23h3.27q.347 0 .577.23t.23.578v.692q0 .348-.23.578T20.29 7h-3.08v9q0 1.246-.876 2.123q-.877.877-2.123.877t-2.123-.877m-7.262-6.374q-.808 1.72-.911 3.682q-.012.233-.155.4T3.404 16q-.233 0-.366-.18t-.122-.414q.123-2.175 1.006-4.072q.884-1.897 2.315-3.328T9.555 5.7t4.062-.997q.233-.012.414.122t.18.366q0 .214-.168.357t-.4.155q-1.962.104-3.67.899T6.95 8.713T4.827 11.75m3.829 1.623q-.47.972-.562 2.095q-.036.233-.18.383t-.356.15t-.354-.168q-.14-.168-.129-.382q.098-1.33.647-2.474q.55-1.143 1.436-2.03t2.03-1.435t2.473-.647q.214-.012.382.128q.169.14.169.354t-.15.357t-.383.18q-1.123.092-2.092.558T9.87 11.654t-1.215 1.718");
}

</style>
