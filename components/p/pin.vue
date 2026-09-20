<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iddesy17d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iddesy17d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:pin" /></template>
