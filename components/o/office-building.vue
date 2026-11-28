<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu631ubgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu631ubgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:office-building" /></template>
