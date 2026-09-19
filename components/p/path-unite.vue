<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mythdnbqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mythdnbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:path-unite" /></template>
