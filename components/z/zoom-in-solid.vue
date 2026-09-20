<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs4p0ceyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zs4p0ceyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:zoom-in-solid" /></template>
