<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuiuvccee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cuiuvccee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:save-2-fill" /></template>
