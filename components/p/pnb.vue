<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hufe2dbzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hufe2dbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pnb" /></template>
