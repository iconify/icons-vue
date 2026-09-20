<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu9gl7b9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lu9gl7b9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ranking-filled" /></template>
