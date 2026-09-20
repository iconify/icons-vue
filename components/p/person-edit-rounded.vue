<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q91l1mmrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-edit-rounded" /></template>
<style>
.q91l1mmrz {
  fill: currentColor;
  d: path("M14.23 19.192v-.73q0-.323.135-.628q.133-.305.35-.522l4.848-4.83q.148-.128.308-.19q.16-.061.32-.061q.165 0 .334.064q.17.065.298.194l.925.944q.123.148.187.308q.065.159.065.319t-.052.322t-.2.31l-4.829 4.83q-.217.217-.522.347q-.305.131-.628.131h-.73q-.348 0-.578-.23t-.23-.578M5 17.808v-.839q0-.619.36-1.159q.361-.539.97-.837q1.416-.679 2.834-1.018q1.417-.34 2.836-.34q.675 0 1.354.084t1.367.238l-2.154 2.154q-.348.347-.534.792t-.187.928v.804H5.808q-.348 0-.578-.23T5 17.808m15.19-2.793l.925-.956l-.924-.943l-.95.95zM9.878 10.509Q9 9.63 9 8.385t.877-2.123T12 5.385t2.123.877T15 8.385t-.877 2.123t-2.123.877t-2.123-.877");
}

</style>
