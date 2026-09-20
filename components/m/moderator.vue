<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuiv1f9nq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uuiv1f9nq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:moderator" /></template>
