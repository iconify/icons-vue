<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="q7p2oszos"/><path class="p5j1ykynj"/><g class="gr7bnx5qp"><path class="lrqo0wj5d"/><path class="mtm7-ibot"/></g><circle class="dkhx4bcze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:tropical-fish" /></template>
<style>
.dkhx4bcze {
  cx: 9.5px;
  cy: 15.5px;
  r: 1.5px;
  fill: var(--svg-color--292f33, #292f33);
}

.gr7bnx5qp {
  fill: var(--svg-color--f4900c, #f4900c);
}

.lrqo0wj5d {
  d: path("M18.001 17.967a1 1 0 0 0 .966 1.032l.034.001a1 1 0 0 0 .998-.967c.201-6.065 5.758-8.816 6.35-9.092a14 14 0 0 0-1.51-1.467c-1.885 1.057-6.634 4.323-6.838 10.493m5.018-2.163a1 1 0 0 0 1.962.392c.516-2.581 2.296-3.574 3.592-3.956a16 16 0 0 0-1.028-1.768c-1.877.691-3.908 2.246-4.526 5.332");
}

.mtm7-ibot {
  d: path("M13 20a1 1 0 1 0 2 0c0-8.97 5.841-12.544 8.266-13.641a12.4 12.4 0 0 0-2.205-1.067C17.888 7.169 13 11.446 13 20");
}

.p5j1ykynj {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M35 9c-1.611 0-4.059 2.972-5.268 6.294c-1.475-5.62-6.166-10.739-12.945-10.739c-8.273 0-12.061 10.216-14.524 14.479c-.629 1.091-4.091 1.034-.989 3.103c-3.103 2.068.449 2.243 1.222 3.103c2.625 2.92 8.997 6.205 14.291 6.205c5.655 0 11.12-3.786 12.863-8.958C30.828 25.896 33.353 29 35 29c2.209 0-2-5.582-2-10s4.209-10 2-10");
}

.q7p2oszos {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M8.231 10c6-8 14-10 18-10c1 0 1 1 0 1s-6 2-7 9s-11 0-11 0m-1 18c4 3 13 8 18 8c3 0 2-1 1-1s-9-3-10-7s-9 0-9 0");
}

</style>
