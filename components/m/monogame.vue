<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzk3ncg5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzk3ncg5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:monogame" /></template>
