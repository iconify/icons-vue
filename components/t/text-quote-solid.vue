<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf0xxccbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tf0xxccbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:text-quote-solid" /></template>
