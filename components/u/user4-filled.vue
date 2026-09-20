<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_jv0bcna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_jv0bcna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user4-filled" /></template>
