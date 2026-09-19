<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iahw3kbqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":24};
const content = `<path class="iahw3kbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:volume-mute" /></template>
