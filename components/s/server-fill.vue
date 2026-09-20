<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtjtxw7qd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtjtxw7qd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:server-fill" /></template>
