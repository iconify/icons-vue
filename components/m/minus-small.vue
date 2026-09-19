<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj4-u8bbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj4-u8bbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:minus-small" /></template>
