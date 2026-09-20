<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz4b3lhfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz4b3lhfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:text-color-fill" /></template>
