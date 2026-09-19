<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-5qcnbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="c-5qcnbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:mute" /></template>
