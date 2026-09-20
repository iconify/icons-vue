<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hme_mebaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hme_mebaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:microphone-cancelled" /></template>
