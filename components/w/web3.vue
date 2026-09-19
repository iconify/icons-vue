<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzf7p8kpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="tzf7p8kpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:web3" /></template>
