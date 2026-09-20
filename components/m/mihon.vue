<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg6lk8tud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jg6lk8tud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:mihon" /></template>
