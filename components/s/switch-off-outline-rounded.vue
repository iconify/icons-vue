<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz8yy7ban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:switch-off-outline-rounded" /></template>
<style>
.uz8yy7ban {
  fill: currentColor;
  d: path("M17.404 3q.69 0 1.153.463t.462 1.152v14.77q0 .69-.462 1.152T17.404 21H6.616q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3zm-.02 1H6.596q-.269 0-.442.173t-.173.443v14.769q0 .269.173.442t.442.173h10.789q.269 0 .452-.173q.182-.173.182-.443L18 4.616q0-.27-.173-.443T17.385 4M14.5 7.712H9.542q-.351 0-.581.232t-.23.575v6.943q0 .343.232.575t.576.232h4.958q.351 0 .581-.232t.23-.575V8.519q0-.343-.232-.575t-.576-.232m-.192 1v4.673H9.73V8.71zm-2.304 8.75q-.29 0-.484.19t-.193.479t.19.484t.48.193t.483-.19t.193-.48t-.19-.483t-.48-.194m0-12.288q-.29 0-.483.19t-.193.48t.19.493t.48.203t.483-.203t.193-.493t-.19-.48t-.48-.19M12 12");
}

</style>
