<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur2ueebmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ur2ueebmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:play-circle-outline" /></template>
