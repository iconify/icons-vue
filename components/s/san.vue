<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug3hazb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":425,"height":512};
const content = `<path class="ug3hazb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:san" /></template>
