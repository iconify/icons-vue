<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbvgthxxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mbvgthxxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:phone-mobile-phone-remix" /></template>
