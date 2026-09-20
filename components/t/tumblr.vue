<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rus6xc84h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rus6xc84h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tumblr" /></template>
