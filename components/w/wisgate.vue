<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl3nhgb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bl3nhgb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:wisgate" /></template>
