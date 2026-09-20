<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df3m-8ghh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="df3m-8ghh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:random-filled" /></template>
