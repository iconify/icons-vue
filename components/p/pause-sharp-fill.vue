<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxp71vylm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxp71vylm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pause-sharp-fill" /></template>
