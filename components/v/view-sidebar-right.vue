<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skc7v0blp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skc7v0blp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:view-sidebar-right" /></template>
