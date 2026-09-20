<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lah41lb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lah41lb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tata" /></template>
