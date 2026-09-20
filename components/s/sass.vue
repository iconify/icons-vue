<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md3vheezs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":384};
const content = `<path class="md3vheezs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sass" /></template>
