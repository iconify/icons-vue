<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqr1_2k-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqr1_2k-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-circle-more-solid" /></template>
