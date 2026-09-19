<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwr1wnz7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwr1wnz7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:snapchat-filled" /></template>
