<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8ew3vpuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="y8ew3vpuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:replyd" /></template>
