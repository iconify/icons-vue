<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwj3j5b2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwj3j5b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:smile-wink-alt" /></template>
