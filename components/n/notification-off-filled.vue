<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4a9j8b8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f4a9j8b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:notification-off-filled" /></template>
