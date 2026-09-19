<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn7txxnka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":512};
const content = `<path class="vn7txxnka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:wenyan" /></template>
