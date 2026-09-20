<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="pcse3_b9d"/><path class="bucvpmn8l"/><path class="rxg2lcbmj"/><path class="j5yp1xbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:mango" /></template>
<style>
.bucvpmn8l {
  fill: var(--svg-color--ea564b, #ea564b);
  d: path("M12.3 3.139c4.545-2.66 11.267-2.611 13.685-.58c1.617 1.358 2.942 2.401 4.474 3.011c2.022.804 3.692 3.154 4.415 5.384c.981 3.023 1.68 12.579-8.029 18.516c-6.233 3.812-17.656 5.363-18.961 4.723c-.984-.483-4.621-2.09-6.675-6.453S-1.324 11.111 12.3 3.139");
}

.j5yp1xbyk {
  fill: var(--svg-color--77b255, #77b255);
  d: path("M28.271 4.278c2.174.697 4.987 4.564 4.944 7.811c-.114 8.655-4.132 11.992-4.132 11.992s-2.551-9.325-2.171-12.719c.278-2.478 1.646-3.166 1.891-4.569c.229-1.305-.532-2.515-.532-2.515");
}

.pcse3_b9d {
  fill: var(--svg-color--77b255, #77b255);
  d: path("M26.38 3.539c.483-.039 1.259-.655 1.664-.595s1.573 1.078 1.67 1.283s-.637 1.178-.746 1.48s-.64.239-1.51-.543c-.869-.782-1.078-1.625-1.078-1.625");
}

.rxg2lcbmj {
  fill: var(--svg-color--f97253, #f97253);
  d: path("M17.329 2.607C22.578 1.125 26.5 4.743 24.078 5c-4.359.463-9.015 4.969-12.625 8.375c-6.625 6.25-8.125 13.75-9 12.5c-1.424-2.034-1.468-9.148 3.561-15.386s9.104-7.257 11.315-7.882");
}

</style>
