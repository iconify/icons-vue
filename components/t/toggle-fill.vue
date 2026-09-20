<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utj6gpbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utj6gpbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:toggle-fill" /></template>
