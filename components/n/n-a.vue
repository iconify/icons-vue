<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6iytebfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6iytebfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:n-a" /></template>
