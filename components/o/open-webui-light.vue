<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtt4lrb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qtt4lrb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:open-webui-light" /></template>
