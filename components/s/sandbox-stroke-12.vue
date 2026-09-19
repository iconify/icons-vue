<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwo4gqime.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="nwo4gqime"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:sandbox-stroke-12" /></template>
