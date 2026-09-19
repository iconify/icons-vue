<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq9kl-b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="tq9kl-b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:sqlite" /></template>
