<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkdcq5bux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mkdcq5bux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:reversehandmiddlefinger" /></template>
