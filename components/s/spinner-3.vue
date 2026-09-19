<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9grvyq5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="f9grvyq5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:spinner-3" /></template>
