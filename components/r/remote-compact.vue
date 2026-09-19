<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6xiyt8wv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="i6xiyt8wv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:remote-compact" /></template>
