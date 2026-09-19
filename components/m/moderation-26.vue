<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq8bp5ypx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="pq8bp5ypx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:moderation-26" /></template>
