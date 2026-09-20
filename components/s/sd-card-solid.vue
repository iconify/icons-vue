<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wskx6_b6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="wskx6_b6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:sd-card-solid" /></template>
