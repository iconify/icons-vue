<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8z-9kbbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8z-9kbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pencil-code" /></template>
