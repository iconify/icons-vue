<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8goy05sw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y8goy05sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:notchedrightsemi3dot" /></template>
