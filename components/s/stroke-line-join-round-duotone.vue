<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9wya7brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary v9wya7brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:stroke-line-join-round-duotone" /></template>
