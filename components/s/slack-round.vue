<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fold3jzin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fold3jzin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:slack-round" /></template>
