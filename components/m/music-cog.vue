<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk88anb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sk88anb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:music-cog" /></template>
