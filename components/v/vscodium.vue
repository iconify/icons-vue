<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9-8sac1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="q9-8sac1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:vscodium" /></template>
