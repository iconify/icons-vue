<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fed2npbfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fed2npbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-9-plus" /></template>
