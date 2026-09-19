<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zoey5m-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zoey5m-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:play-track-next-o" /></template>
