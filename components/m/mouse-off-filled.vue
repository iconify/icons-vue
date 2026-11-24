<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu04c6ibz.css';
import '../../css/l/ly-oin5oy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eu04c6ibz"/><path clip-rule="evenodd" class="ly-oin5oy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mouse-off-filled" /></template>
