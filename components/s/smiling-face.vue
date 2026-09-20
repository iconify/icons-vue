<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="tg31urbgg"/><circle class="b85ymxbrh"/><circle class="ln8k4sbva"/><path class="re3h1o-kv"/><g class="uawwy1jvu"><path class="mql1o4tqm"/><path class="jud_khfhb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:smiling-face" /></template>
<style>
.b85ymxbrh {
  cx: 29px;
  cy: 22px;
  r: 5px;
  fill: var(--svg-color--ff7892, #ff7892);
}

.jud_khfhb {
  d: path("M18 29.5c-4.34 0-5.474-4.335-5.485-4.379a.501.501 0 0 1 .829-.485c.039.034 1.066.864 4.656.864c3.644 0 4.647-.855 4.657-.863a.51.51 0 0 1 .597-.06a.495.495 0 0 1 .231.544C23.474 25.165 22.34 29.5 18 29.5m-4.051-3.492C14.526 27.072 15.724 28.5 18 28.5s3.475-1.428 4.051-2.492c-.82.258-2.101.492-4.051.492s-3.231-.234-4.051-.492M13 25h.01z");
}

.ln8k4sbva {
  cx: 7px;
  cy: 22px;
  r: 5px;
  fill: var(--svg-color--ff7892, #ff7892);
}

.mql1o4tqm {
  d: path("M13 25s1 4 5 4s5-4 5-4s-1 1-5 1s-5-1-5-1");
}

.re3h1o-kv {
  fill: var(--svg-color--664500, #664500);
  d: path("M29 14a1 1 0 0 1-.707-.293c-2.577-2.575-7.055-1.736-7.099-1.726a.996.996 0 0 1-1.174-.787a1 1 0 0 1 .783-1.174c.227-.046 5.563-1.065 8.903 2.273A.999.999 0 0 1 29 14M7 14a.999.999 0 0 1-.707-1.707c3.34-3.341 8.678-2.318 8.903-2.273a1 1 0 0 1-.391 1.962c-.069-.015-4.529-.843-7.098 1.726A1 1 0 0 1 7 14m19 5a1 1 0 0 1-.707-.293c-1.304-1.305-4.09-.974-5.052-.736a1 1 0 0 1-.483-1.941c.186-.046 4.575-1.111 6.949 1.263A.999.999 0 0 1 26 19m-16 0a.999.999 0 0 1-.707-1.707c2.373-2.373 6.764-1.309 6.95-1.263a1 1 0 0 1-.483 1.941c-.964-.237-3.749-.567-5.052.736A1 1 0 0 1 10 19");
}

.tg31urbgg {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M36 18c0 9.941-8.059 18-18 18c-9.94 0-18-8.059-18-18C0 8.06 8.06 0 18 0c9.941 0 18 8.06 18 18");
}

.uawwy1jvu {
  fill: var(--svg-color--664500, #664500);
}

</style>
