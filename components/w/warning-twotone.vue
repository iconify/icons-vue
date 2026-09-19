<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayfgg5nwl.css';
import '../../css/c/ccaa01b9p.css';
import '../../css/j/jej9crbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ayfgg5nwl"/><path class="ccaa01b9p"/><path class="jej9crbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:warning-twotone" /></template>
