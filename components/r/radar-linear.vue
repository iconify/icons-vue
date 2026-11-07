<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftquq3bkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftquq3bkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:radar-linear" /></template>
