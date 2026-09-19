<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia2ea1eon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ia2ea1eon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:x-circle-solid" /></template>
