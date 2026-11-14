<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s94y7jb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:var-review" /></template>
<style>
.s94y7jb9d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 5.82L9.079 2.273q-.047-.057-.104-.104t-.123-.081q-.065-.035-.136-.056q-.07-.021-.144-.029q-.073-.007-.147.001q-.073.007-.144.029q-.071.021-.136.056t-.122.082q-.115.095-.185.227q-.07.131-.085.28q-.014.148.03.291q.043.143.138.258l2.49 3.023H6q-1.76 0-3.005 1.245T1.75 10.5V17q0 1.76 1.245 3.005T6 21.25h12q1.76 0 3.005-1.245T22.25 17v-6.5q0-1.76-1.245-3.005T18 6.25h-4.411l2.49-3.023q.095-.115.138-.258t.03-.291q-.015-.149-.085-.28t-.185-.227q-.057-.047-.122-.082t-.136-.056t-.144-.029t-.147-.001q-.074.008-.144.029q-.071.021-.136.056t-.123.081q-.057.047-.104.104zm.479 5.065l1.504.981q1.02.666 1.02 1.884t-1.02 1.884l-1.504.981q-1.123.732-2.301.094Q9.001 16.071 9 14.731v-1.962q.001-1.34 1.178-1.978t2.301.094");
}

</style>
