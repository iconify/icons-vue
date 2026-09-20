<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-fj8dbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="t-fj8dbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:volume-mute-circle-f" /></template>
