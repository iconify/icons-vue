<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrd_53ogm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="qrd_53ogm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:userfilter" /></template>
