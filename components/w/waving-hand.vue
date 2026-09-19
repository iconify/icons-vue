<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7f-vm4dn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g7f-vm4dn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:waving-hand" /></template>
