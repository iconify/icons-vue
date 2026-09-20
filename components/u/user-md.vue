<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv5n-xbeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tv5n-xbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:user-md" /></template>
