<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7z0dvb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b7z0dvb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:trail-blazes-left" /></template>
