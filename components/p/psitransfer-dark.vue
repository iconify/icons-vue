<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imws7ob2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="imws7ob2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:psitransfer-dark" /></template>
