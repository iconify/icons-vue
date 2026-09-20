<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyv8m4uoe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyv8m4uoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail" /></template>
