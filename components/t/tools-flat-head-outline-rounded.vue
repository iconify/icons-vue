<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0wfsmb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tools-flat-head-outline-rounded" /></template>
<style>
.p0wfsmb2j {
  fill: currentColor;
  d: path("M9 21q-.425 0-.712-.288T8 20t.288-.712T9 19h6q.425 0 .713.288T16 20t-.288.713T15 21zm-.125-3q-.375 0-.663-.238t-.337-.612L7.05 11.4q-.025-.2-.012-.387t.062-.388L8.8 3.75q.075-.35.35-.55t.625-.2h4.45q.35 0 .625.2t.35.55l1.7 6.875q.05.2.063.388t-.013.387l-.825 5.75q-.05.375-.337.613t-.663.237zm.85-2h4.55l.55-4H9.15zM9.3 10h5.4l-1.25-5h-2.9zm4.975 6h-4.55z");
}

</style>
