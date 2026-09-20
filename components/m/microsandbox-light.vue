<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn419zgkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xn419zgkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsandbox-light" /></template>
