<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-_v96bqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-_v96bqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:message-square" /></template>
