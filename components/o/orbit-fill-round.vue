<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmwcp1byk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmwcp1byk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:orbit-fill-round" /></template>
