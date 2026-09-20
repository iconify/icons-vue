<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpz6nsfpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpz6nsfpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:twitter-line" /></template>
