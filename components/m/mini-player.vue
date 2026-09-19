<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te9dwhb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="te9dwhb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:mini-player" /></template>
