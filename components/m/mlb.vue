<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agbkatb_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agbkatb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:mlb" /></template>
