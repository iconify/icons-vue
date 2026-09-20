<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn7zg8bmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vn7zg8bmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:undo-right-round-broken" /></template>
