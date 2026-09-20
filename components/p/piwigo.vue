<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytc8hsbew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytc8hsbew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:piwigo" /></template>
