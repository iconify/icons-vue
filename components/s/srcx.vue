<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0qmicg8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0qmicg8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:srcx" /></template>
