<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm1k1rblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lm1k1rblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:online-medical-service-monitor-solid" /></template>
