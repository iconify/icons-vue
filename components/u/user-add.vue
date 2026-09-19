<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0dl3tbpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0dl3tbpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:user-add" /></template>
