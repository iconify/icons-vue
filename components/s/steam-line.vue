<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8zpm-b6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8zpm-b6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:steam-line" /></template>
