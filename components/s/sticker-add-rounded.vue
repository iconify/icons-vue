<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8bejmeom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sticker-add-rounded" /></template>
<style>
.r8bejmeom {
  fill: currentColor;
  d: path("M19 5h-1.5q-.213 0-.356-.144T17 4.499t.144-.356T17.5 4H19V2.5q0-.213.144-.356T19.501 2t.356.144T20 2.5V4h1.5q.213 0 .356.144t.144.357t-.144.356T21.5 5H20v1.5q0 .213-.144.356T19.499 7t-.356-.144T19 6.5zm-5.573 4.27l2.38-.674q.068-.565-.323-.985q-.392-.419-.984-.419q-.545 0-.926.382t-.382.926q0 .217.072.4q.07.183.163.37m-6 1.75l2.38-.674q.062-.565-.325-.985t-.991-.419q-.539 0-.919.382q-.38.381-.38.926q0 .217.072.4q.07.183.163.37m4.073 3.71q1.494 0 2.654-.922q1.16-.923 1.5-2.373L8.5 13.454q.592.627 1.367.952t1.633.325M15 19l4-4h-2q-.825 0-1.412.588T15 17zm-9.385 1q-.666 0-1.14-.475T4 18.386V5.615q0-.666.475-1.14T5.615 4h8.412q.236 0 .404.167q.167.168.167.41q0 .959.39 1.828t1.064 1.543t1.543 1.063t1.828.391q.243 0 .41.167q.167.168.167.404v4.933q0 .331-.13.632t-.349.518l-3.465 3.465q-.218.218-.518.348t-.632.131z");
}

</style>
