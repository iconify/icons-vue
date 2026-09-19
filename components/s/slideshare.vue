<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv452rm2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":669,"height":681};
const content = `<path class="xv452rm2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:slideshare" /></template>
