<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh8ehk5lh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oh8ehk5lh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:signal" /></template>
