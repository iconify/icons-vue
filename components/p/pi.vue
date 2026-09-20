<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptj-dkj5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptj-dkj5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:pi" /></template>
