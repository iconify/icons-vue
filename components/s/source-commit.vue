<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go8lz-9sr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go8lz-9sr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:source-commit" /></template>
