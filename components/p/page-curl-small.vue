<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esgs_iocj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="esgs_iocj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:page-curl-small" /></template>
