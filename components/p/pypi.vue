<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfa7lr5ki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":454,"height":512};
const content = `<path class="nfa7lr5ki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:pypi" /></template>
