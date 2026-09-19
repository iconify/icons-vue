<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkcvembuk.css';
import '../../css/a/au89ljb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lkcvembuk"/><path class="au89ljb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:stormcloud" /></template>
