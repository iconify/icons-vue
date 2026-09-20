<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l60g_u.css';
import '../../css/d/d-opowom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l60g_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:twitter-x-alt" /></template>
