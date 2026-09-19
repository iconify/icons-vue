<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8j3y9bdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":24};
const content = `<path class="w8j3y9bdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:webpack" /></template>
