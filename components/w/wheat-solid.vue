<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9u_4xbqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9u_4xbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:wheat-solid" /></template>
