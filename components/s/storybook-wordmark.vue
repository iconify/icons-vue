<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4sclebpp.css';
import '../../css/o/o1kac1bzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="o4sclebpp"/><path class="o1kac1bzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:storybook-wordmark" /></template>
