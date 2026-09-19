<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqjbld-4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rqjbld-4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:taobao" /></template>
