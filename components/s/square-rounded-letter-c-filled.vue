<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f54y-9dgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f54y-9dgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-letter-c-filled" /></template>
