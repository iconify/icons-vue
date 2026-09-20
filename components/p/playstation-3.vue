<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/talh9rb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="talh9rb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:playstation-3" /></template>
