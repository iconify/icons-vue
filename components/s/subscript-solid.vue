<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7b54abma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7b54abma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:subscript-solid" /></template>
