<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0isaxfvi.css';
import '../../css/z/znm6qw9zy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="z0isaxfvi"/><path class="znm6qw9zy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:waku" /></template>
