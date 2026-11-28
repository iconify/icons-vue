<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqbde7trk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqbde7trk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:tabs-x" /></template>
