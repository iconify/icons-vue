<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wahtxdb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wahtxdb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:megaphone-filled" /></template>
