<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq_72vemr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dq_72vemr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-cloud-circle" /></template>
