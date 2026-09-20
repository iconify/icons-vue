<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbtjk6bah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qbtjk6bah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:tune-adjust-volume" /></template>
