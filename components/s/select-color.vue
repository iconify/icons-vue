<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bibyrib3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bibyrib3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:select-color" /></template>
