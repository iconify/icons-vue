<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj-hdumnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aj-hdumnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:umbrella" /></template>
