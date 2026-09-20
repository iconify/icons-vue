<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/koi-z9b7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="koi-z9b7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:wampl" /></template>
