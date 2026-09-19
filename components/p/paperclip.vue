<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo1736mqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="mo1736mqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:paperclip" /></template>
