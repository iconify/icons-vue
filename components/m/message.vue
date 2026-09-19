<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh38uqbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dh38uqbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:message" /></template>
