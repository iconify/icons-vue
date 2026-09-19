<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2zeo2byx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x2zeo2byx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:varicose-vein-24px" /></template>
