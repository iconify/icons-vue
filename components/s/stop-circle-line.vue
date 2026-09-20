<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzsr9gn5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzsr9gn5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:stop-circle-line" /></template>
