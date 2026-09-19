<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsfw2vjvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsfw2vjvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:visa" /></template>
