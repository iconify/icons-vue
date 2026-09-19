<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyo_5k1_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyo_5k1_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:reduce" /></template>
