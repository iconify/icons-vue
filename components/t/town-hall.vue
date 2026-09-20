<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg0rhxb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tg0rhxb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:town-hall" /></template>
