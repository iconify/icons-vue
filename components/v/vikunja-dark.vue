<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axej3o6of.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="axej3o6of"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vikunja-dark" /></template>
