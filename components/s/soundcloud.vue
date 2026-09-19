<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqbt5cble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":622};
const content = `<path class="pqbt5cble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:soundcloud" /></template>
