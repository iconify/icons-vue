<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rew5u3t-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="rew5u3t-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:waxing-crescent-moon-symbol" /></template>
