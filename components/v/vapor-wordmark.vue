<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo6_k6b5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bo6_k6b5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:vapor-wordmark" /></template>
