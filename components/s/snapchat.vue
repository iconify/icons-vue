<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9hdpufda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":24};
const content = `<path class="v9hdpufda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:snapchat" /></template>
