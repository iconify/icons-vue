<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlzjzn_rv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mail-spark-rounded" /></template>
<style>
.jlzjzn_rv {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v5.201q0 .243-.195.383t-.432.054q-1.71-.562-3.466-.154t-3.078 1.729q-.921.921-1.409 2.107q-.487 1.185-.486 2.487q.012.223-.15.4q-.161.177-.378.177zm13.788 3.5q-.15 0-.2-.15q-.362-1.39-1.359-2.387t-2.387-1.36q-.15-.05-.15-.2q0-.174.15-.2q1.39-.36 2.387-1.358q.997-.997 1.359-2.387q.05-.15.2-.15q.169 0 .2.15q.361 1.39 1.358 2.387t2.388 1.359q.15.025.15.2q0 .15-.15.2q-1.39.362-2.388 1.359t-1.358 2.387q-.025.15-.2.15M12 11L4.82 6.32q-.195-.122-.402-.045t-.264.289q-.058.148-.015.306q.042.159.184.246l7.108 4.638q.269.165.569.165t.57-.165l7.107-4.638q.142-.087.194-.246t-.025-.307q-.057-.211-.264-.279q-.207-.067-.401.054z");
}

</style>
