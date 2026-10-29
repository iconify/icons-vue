<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok-_polxz.css';
import '../../css/a/azxuvfb9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ok-_polxz"/><path class="azxuvfb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:menu" /></template>
