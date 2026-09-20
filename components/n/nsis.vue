<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn8tvia-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mn8tvia-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nsis" /></template>
