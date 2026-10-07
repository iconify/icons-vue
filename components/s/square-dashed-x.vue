<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9bgmi4jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9bgmi4jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-dashed-x" /></template>
