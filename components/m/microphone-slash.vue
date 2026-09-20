<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xshqbbt3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xshqbbt3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:microphone-slash" /></template>
