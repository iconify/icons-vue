<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjc2acbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tjc2acbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:minus-solid" /></template>
