<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-vjr-y9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-vjr-y9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:smugmug" /></template>
