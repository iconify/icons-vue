<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm5rxtu_s.css';
import '../../css/y/yqxcomdtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lm5rxtu_s"/><path class="yqxcomdtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:skin-twotone" /></template>
