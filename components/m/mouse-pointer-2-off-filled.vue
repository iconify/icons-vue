<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrizkoc3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrizkoc3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mouse-pointer-2-off-filled" /></template>
