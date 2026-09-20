<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4xookb9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4xookb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:mikrotik" /></template>
