<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mndd9jbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mndd9jbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:play-expressive" /></template>
