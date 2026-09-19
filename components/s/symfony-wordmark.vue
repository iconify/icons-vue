<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnlpitc9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jnlpitc9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:symfony-wordmark" /></template>
