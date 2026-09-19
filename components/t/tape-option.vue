<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/row95eb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="row95eb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:tape-option" /></template>
