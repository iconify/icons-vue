<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd-_aub3g.css';
import '../../css/f/fss4rybej.css';
import '../../css/i/ia58y6bdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dd-_aub3g wm-k"/><path class="fss4rybej wm-a"/><path class="ia58y6bdf wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:move" /></template>
