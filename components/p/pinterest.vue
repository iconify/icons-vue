<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de85xv_ov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":832,"height":1025};
const content = `<path class="de85xv_ov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pinterest" /></template>
