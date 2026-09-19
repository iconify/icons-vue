<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su52d4bzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="su52d4bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:triangle-inverted-small" /></template>
