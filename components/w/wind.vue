<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv212v18f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":24};
const content = `<path class="vv212v18f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:wind" /></template>
