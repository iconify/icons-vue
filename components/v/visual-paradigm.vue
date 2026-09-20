<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv3iph2kk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mv3iph2kk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:visual-paradigm" /></template>
