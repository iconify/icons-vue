<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1crgvb3e.css';
import '../../css/t/t694e9bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":375,"height":512};
const content = `<path class="s1crgvb3e"/><path class="t694e9bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:parrot" /></template>
