<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io42-nhcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io42-nhcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:monster" /></template>
