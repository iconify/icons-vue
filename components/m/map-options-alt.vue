<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm_6fobjp.css';
import '../../css/h/h1ytemzns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="hm_6fobjp"/><path class="h1ytemzns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:map-options-alt" /></template>
