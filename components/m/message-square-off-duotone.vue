<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_ts1cluy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_ts1cluy primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-square-off-duotone" /></template>
