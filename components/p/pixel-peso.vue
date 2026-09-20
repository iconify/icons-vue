<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-khjx3hw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d-khjx3hw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-peso" /></template>
