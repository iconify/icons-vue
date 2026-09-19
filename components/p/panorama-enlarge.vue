<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjyf8l7ig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjyf8l7ig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:panorama-enlarge" /></template>
