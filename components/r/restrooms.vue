<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd3tmjb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="bd3tmjb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:restrooms" /></template>
