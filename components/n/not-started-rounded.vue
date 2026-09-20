<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1vw3w94v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:not-started-rounded" /></template>
<style>
.s1vw3w94v {
  fill: currentColor;
  d: path("M9.713 15.713Q10 15.425 10 15V9q0-.425-.288-.712T9 8t-.712.288T8 9v6q0 .425.288.713T9 16t.713-.288m3.462-.487l3.9-2.6q.35-.225.35-.625t-.35-.625l-3.9-2.6q-.375-.25-.775-.038T12 9.4v5.2q0 .45.4.663t.775-.038M12 22q-2.075 0-3.9-.788t-3.175-2.137T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22");
}

</style>
