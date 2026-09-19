<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqu0-5bax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="fqu0-5bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:xiaoyuzhou" /></template>
