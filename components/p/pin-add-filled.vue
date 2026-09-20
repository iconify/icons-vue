<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4rk8eb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s4rk8eb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pin-add-filled" /></template>
