<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr4511a7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nr4511a7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:plus-outline" /></template>
