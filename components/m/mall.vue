<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk99xzecf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lk99xzecf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:mall" /></template>
