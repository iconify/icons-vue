<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl6gyl07q.css';
import '../../css/h/hxv6wjbvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yl6gyl07q"/><path class="hxv6wjbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:swiparr" /></template>
