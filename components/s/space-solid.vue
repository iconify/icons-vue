<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9w16w2hz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9w16w2hz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:space-solid" /></template>
