<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb8ls8bmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb8ls8bmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:package-clock" /></template>
