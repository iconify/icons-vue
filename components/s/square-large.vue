<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1b1yq60o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a1b1yq60o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:square-large" /></template>
