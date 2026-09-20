<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsc7y1b_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jsc7y1b_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:phorge-light" /></template>
