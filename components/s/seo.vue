<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb64r8bnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1025};
const content = `<path class="gb64r8bnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:seo" /></template>
