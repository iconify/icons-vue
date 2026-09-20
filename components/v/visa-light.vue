<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-9bxbbqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z-9bxbbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:visa-light" /></template>
