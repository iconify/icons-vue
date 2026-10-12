<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxuzxz-mq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vxuzxz-mq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:x-circle-fill-20" /></template>
