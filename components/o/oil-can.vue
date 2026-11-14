<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pm6q-bbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:oil-can" /></template>
<style>
.pm6q-bbbu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.58 8.842q-.027-.045-.056-.089l8.367-5.113q.063-.039.117-.089t.098-.109t.075-.127t.048-.139t.02-.146q.003-.073-.008-.146q-.012-.073-.037-.143q-.026-.069-.064-.132q-.078-.127-.198-.215t-.266-.123t-.292-.012q-.148.023-.275.101l-8.912 5.446q-.257-.056-.546-.056H8.349q-1.274 0-1.929 1.092l-.313.522q-.306.51-.225 1.025q-1.058.276-1.887 1.106Q2.75 12.74 2.75 14.5V18q0 1.76 1.245 3.005T7 22.25h5q1.76 0 3.005-1.245T16.25 18v-3.5q0-1.76-1.245-3.005q-.829-.83-1.887-1.106q.081-.515-.225-1.025z");
}

</style>
