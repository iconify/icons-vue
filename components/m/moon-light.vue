<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmx5yk91i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmx5yk91i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:moon-light" /></template>
