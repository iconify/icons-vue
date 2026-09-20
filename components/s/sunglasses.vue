<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdknls8fh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdknls8fh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sunglasses" /></template>
