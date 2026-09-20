<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-0onelyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-0onelyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:vivino" /></template>
