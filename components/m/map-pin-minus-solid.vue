<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdg6b-bbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdg6b-bbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:map-pin-minus-solid" /></template>
