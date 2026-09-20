<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7jb9-9qt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l7jb9-9qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:power-transformer" /></template>
