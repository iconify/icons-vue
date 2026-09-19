<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm9r7-bec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="tm9r7-bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:mail" /></template>
