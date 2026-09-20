<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsr5jwd6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rsr5jwd6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:reply-outline" /></template>
