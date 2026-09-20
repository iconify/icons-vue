<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu-6g1b6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eu-6g1b6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:radarr" /></template>
