<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3ig00-8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3ig00-8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:thin-big-left" /></template>
