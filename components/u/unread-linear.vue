<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4sn9nawv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4sn9nawv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:unread-linear" /></template>
