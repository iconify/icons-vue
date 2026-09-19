<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn8mvjb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zn8mvjb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:sass" /></template>
