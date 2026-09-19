<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dquv7marm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dquv7marm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:star-half" /></template>
