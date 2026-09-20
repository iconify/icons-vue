<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpf9e0yer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dpf9e0yer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:youtube-fill" /></template>
