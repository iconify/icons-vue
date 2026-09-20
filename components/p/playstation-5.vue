<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t68sc978p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t68sc978p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:playstation-5" /></template>
