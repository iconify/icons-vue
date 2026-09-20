<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghapr57hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghapr57hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ritz-carlton" /></template>
