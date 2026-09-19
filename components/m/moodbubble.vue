<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7wky1pgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n7wky1pgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:moodbubble" /></template>
