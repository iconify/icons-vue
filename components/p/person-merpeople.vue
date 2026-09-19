<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iptj19dee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iptj19dee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:person-merpeople" /></template>
