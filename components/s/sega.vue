<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3livcc1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3livcc1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sega" /></template>
