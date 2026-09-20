<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc3j7ypou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yc3j7ypou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openbao-dark" /></template>
