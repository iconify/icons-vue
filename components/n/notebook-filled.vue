<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdyjpsboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bdyjpsboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:notebook-filled" /></template>
