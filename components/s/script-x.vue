<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvb0xcbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvb0xcbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:script-x" /></template>
