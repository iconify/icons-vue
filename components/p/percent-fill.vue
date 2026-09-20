<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4r8w8b0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4r8w8b0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:percent-fill" /></template>
