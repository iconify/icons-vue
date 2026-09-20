<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b00az4bsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b00az4bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:umami-dark" /></template>
