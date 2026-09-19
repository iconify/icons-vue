<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl-q4qtnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1280,"height":1536};
const content = `<path class="kl-q4qtnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:shield" /></template>
