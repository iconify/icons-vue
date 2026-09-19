<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekqxg0bdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ekqxg0bdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:sparkles-solid" /></template>
