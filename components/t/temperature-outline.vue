<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux428-b9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ux428-b9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:temperature-outline" /></template>
