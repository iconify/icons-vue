<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cum7zpodp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cum7zpodp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:tinder-logo-block" /></template>
