<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmjg9xeev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmjg9xeev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shield-key-outline" /></template>
