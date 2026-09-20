<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh0-oqbui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gh0-oqbui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:postgresql" /></template>
