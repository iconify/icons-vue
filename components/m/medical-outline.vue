<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh6pq3bmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dh6pq3bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:medical-outline" /></template>
