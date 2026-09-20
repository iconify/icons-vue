<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teyrvibbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="teyrvibbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:water-filled" /></template>
