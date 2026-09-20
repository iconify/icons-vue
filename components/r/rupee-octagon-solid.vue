<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkmn4cfof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkmn4cfof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:rupee-octagon-solid" /></template>
