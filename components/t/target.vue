<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxji-uapf.css';
import '../../css/d/dqouzac4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer gxji-uapf"/><path class="dqouzac4x duoicon-primary-layer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:target" /></template>
