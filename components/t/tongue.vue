<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr_jmhjqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fr_jmhjqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:tongue" /></template>
