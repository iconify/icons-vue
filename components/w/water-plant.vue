<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by7szym1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="by7szym1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:water-plant" /></template>
