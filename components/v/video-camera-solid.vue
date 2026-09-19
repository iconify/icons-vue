<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9hqm9bkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q9hqm9bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:video-camera-solid" /></template>
