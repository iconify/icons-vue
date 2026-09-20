<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu43gsb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tu43gsb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:tomtom" /></template>
