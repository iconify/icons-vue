<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asaqj9qwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asaqj9qwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:podium" /></template>
