<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6kz7fbvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6kz7fbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:member-filled" /></template>
