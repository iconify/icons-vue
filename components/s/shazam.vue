<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0xma3bkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0xma3bkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:shazam" /></template>
