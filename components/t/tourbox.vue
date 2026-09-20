<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/romdbj0mh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="romdbj0mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tourbox" /></template>
