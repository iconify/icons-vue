<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh_2ys6yn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gh_2ys6yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:nextdoor" /></template>
