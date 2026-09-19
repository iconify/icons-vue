<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eahdk6b0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eahdk6b0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:openzfs" /></template>
