<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfl4o4bxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfl4o4bxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:phone" /></template>
