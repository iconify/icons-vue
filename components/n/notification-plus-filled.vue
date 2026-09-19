<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6bskxbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6bskxbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:notification-plus-filled" /></template>
