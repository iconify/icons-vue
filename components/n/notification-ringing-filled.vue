<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2ki8fuuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u2ki8fuuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:notification-ringing-filled" /></template>
