<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn6f7hbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zn6f7hbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:threat-document-solid" /></template>
