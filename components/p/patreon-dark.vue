<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etba4kbfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":40};
const content = `<path class="etba4kbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:patreon-dark" /></template>
