<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9hia6hcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9hia6hcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:phone" /></template>
