<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujhv2izwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ujhv2izwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:running-2-outline" /></template>
