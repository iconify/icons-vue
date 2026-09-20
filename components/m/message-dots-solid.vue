<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz1mh80qz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz1mh80qz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:message-dots-solid" /></template>
