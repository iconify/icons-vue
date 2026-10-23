<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv2qgqb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kv2qgqb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:users-round" /></template>
