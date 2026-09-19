<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu1a9m03i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yu1a9m03i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:message-minus" /></template>
