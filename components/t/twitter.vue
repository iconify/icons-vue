<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocaw4rbal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ocaw4rbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:twitter" /></template>
