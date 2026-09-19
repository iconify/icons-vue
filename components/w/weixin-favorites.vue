<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7vsc55kd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l7vsc55kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:weixin-favorites" /></template>
