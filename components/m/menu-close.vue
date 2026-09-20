<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/api0k3bdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="api0k3bdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:menu-close" /></template>
