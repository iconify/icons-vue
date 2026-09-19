<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2k3m0xzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="h2k3m0xzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:petri-dish" /></template>
