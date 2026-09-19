<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3_41eo6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="w3_41eo6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:record-keys-compact" /></template>
