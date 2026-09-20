<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuk24k_kt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuk24k_kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:redux-saga" /></template>
