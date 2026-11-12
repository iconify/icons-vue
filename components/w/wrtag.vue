<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn4_-syio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xn4_-syio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wrtag" /></template>
