<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqpg8_bbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cqpg8_bbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yamlresume-dark" /></template>
