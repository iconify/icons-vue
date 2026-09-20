<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukdgz6b1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ukdgz6b1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:viewpoint" /></template>
