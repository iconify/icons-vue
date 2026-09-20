<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgvxcybnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgvxcybnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:post-it-notes" /></template>
