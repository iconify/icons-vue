<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv6gb4cyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv6gb4cyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:resharper" /></template>
