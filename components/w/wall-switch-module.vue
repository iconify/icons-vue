<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avywr9bui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avywr9bui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wall-switch-module" /></template>
