<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8pl06b_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k8pl06b_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:refresh-1-fill" /></template>
