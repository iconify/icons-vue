<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvygl72pc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="nvygl72pc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:smirking-face" /></template>
