<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-m6x_4pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-m6x_4pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:notifications-alt-line" /></template>
