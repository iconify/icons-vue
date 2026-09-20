<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo94e-b0r.css';
import '../../css/e/enjmbiu9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fo94e-b0r"/><path class="enjmbiu9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:pro" /></template>
