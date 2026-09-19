<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzqw2jbop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xzqw2jbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:notification-fill-12" /></template>
