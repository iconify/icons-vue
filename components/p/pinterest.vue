<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqsl67uft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="aqsl67uft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:pinterest" /></template>
