<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjd0hm9at.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjd0hm9at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:video-slash" /></template>
