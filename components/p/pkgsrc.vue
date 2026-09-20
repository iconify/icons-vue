<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktl4fubtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktl4fubtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pkgsrc" /></template>
