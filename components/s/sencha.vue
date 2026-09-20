<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcodp_bdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcodp_bdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sencha" /></template>
