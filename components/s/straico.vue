<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho4am6oor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ho4am6oor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:straico" /></template>
