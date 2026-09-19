<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj3n62b3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cj3n62b3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tailwind" /></template>
