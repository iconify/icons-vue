<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3b4-qbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3b4-qbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rocket" /></template>
