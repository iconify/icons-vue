<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g87wobb9j.css';
import '../../css/n/nbgk0wbrq.css';
import '../../css/d/dj35aibbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g87wobb9j"/><path class="nbgk0wbrq"/><path class="dj35aibbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:people-nearby-bold" /></template>
