<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_-js4h4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_-js4h4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:three-finger-05" /></template>
