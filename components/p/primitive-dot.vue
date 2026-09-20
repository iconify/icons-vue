<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frspmqwww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":16};
const content = `<path class="frspmqwww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:primitive-dot" /></template>
