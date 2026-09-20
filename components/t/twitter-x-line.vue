<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmb6m4bku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmb6m4bku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:twitter-x-line" /></template>
