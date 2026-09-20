<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhtl3hy3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="yhtl3hy3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:text-telephone" /></template>
