<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-kg8npvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o-kg8npvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:webcam-video" /></template>
