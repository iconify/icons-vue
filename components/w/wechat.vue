<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2e-zacas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s2e-zacas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wechat" /></template>
