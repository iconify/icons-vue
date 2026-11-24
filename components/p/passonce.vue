<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfcghdbkz.css';
import '../../css/y/ycfegbxjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="cfcghdbkz"/><path class="ycfegbxjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:passonce" /></template>
