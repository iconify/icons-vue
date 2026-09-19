<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-41nfxjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f-41nfxjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:playstation4" /></template>
