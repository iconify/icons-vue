<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3pjw8e7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3pjw8e7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:proxy" /></template>
