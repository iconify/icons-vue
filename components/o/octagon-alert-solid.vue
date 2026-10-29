<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5jbh9b2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5jbh9b2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:octagon-alert-solid" /></template>
