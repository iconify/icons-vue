<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpx5-6bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpx5-6bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:people-filled" /></template>
