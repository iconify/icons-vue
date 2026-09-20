<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kms9x3bpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:switch-off-outline" /></template>
<style>
.kms9x3bpy {
  fill: currentColor;
  d: path("M17.404 3q.69 0 1.153.463t.462 1.152v14.77q0 .69-.462 1.152T17.404 21H6.616q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3zm-.02 1H6.596q-.269 0-.442.173t-.173.443v14.769q0 .269.173.442t.442.173h10.789q.269 0 .452-.173q.182-.173.182-.443L18 4.616q0-.27-.173-.443T17.385 4m-2.077 3.712H8.73v8.557h6.577zm-1 1v4.673H9.73V8.71zM12 17.462q-.286 0-.48.193t-.193.48t.193.48t.48.193t.48-.194t.193-.48q0-.286-.193-.48t-.48-.192m0-12.289q-.287 0-.48.193t-.193.48t.193.49t.48.202t.48-.203t.193-.489t-.193-.48t-.48-.193M12 12");
}

</style>
