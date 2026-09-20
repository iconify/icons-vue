<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgd02jb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgd02jb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:person-add" /></template>
