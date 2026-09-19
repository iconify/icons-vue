<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auu3qccwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="auu3qccwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:map" /></template>
