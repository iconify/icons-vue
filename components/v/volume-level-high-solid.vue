<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn1jyfb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xn1jyfb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:volume-level-high-solid" /></template>
