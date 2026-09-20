<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9awnsrhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9awnsrhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:user-star-fill" /></template>
