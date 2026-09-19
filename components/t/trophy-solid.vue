<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me89-bcny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="me89-bcny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:trophy-solid" /></template>
