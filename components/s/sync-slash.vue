<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vai96navg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vai96navg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:sync-slash" /></template>
