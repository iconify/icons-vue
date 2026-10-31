<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho-7w3yfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ho-7w3yfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-list-round" /></template>
