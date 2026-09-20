<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp6o6d8oj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fp6o6d8oj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:oculus-logo-solid" /></template>
