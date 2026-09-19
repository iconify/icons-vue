<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/racr9cchc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="racr9cchc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:refrigeration" /></template>
