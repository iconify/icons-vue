<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd5s3xe8a.css';
import '../../css/k/kbk8q-9yx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cd5s3xe8a"/><path class="kbk8q-9yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:spatula-48" /></template>
