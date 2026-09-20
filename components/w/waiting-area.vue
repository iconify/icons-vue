<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9a21gb4v.css';
import '../../css/y/y5y8shbyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="w9a21gb4v"/><path class="y5y8shbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:waiting-area" /></template>
