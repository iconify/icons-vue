<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftg0kf3yu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ftg0kf3yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:volume-max" /></template>
