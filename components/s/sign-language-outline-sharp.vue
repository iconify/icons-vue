<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyegcfubj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sign-language-outline-sharp" /></template>
<style>
.zyegcfubj {
  fill: currentColor;
  d: path("m7.51 18.04l-5.627-1.05l.176-.988l5.732 1.07zm.911-3.246l-6.469-1.778l.3-.964l6.444 1.779zM11.433 22l-8.727-.779l.123-1L11.53 21q.86.094 1.556-.395q.696-.49.934-1.324l1.217-4.395q.07-.227.067-.459q-.003-.233-.116-.46L13.083 9.93l-.164 3.525l-8.083-4.168l.497-.87l6.634 3.428l.164-3.019l1.396-.308l2.57 5.08q.2.378.214.792q.016.413-.109.798l-1.218 4.375q-.317 1.169-1.324 1.869T11.433 22M8.706 8.025L7.223 6.273l.762-.634l2.298 2.734l-.012.475zm3.583-1.27l-2.431-3.49l.829-.592l2.732 3.952zm5.875 8.107q.028-.287.022-.58t-.09-.578l.708-.477q.207-.138.353-.324q.145-.186.195-.437l1.198-4.697l-2.604 2.848l-3.471-8.334l.927-.41l2.867 6.89l2.283-2.532l1.292.671l-1.529 5.856q-.111.404-.344.73t-.58.543zm-.218-4.245");
}

</style>
