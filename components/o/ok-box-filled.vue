<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iub-4pq8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="iub-4pq8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:ok-box-filled" /></template>
