<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsgpmlo2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsgpmlo2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:share-2-fill" /></template>
