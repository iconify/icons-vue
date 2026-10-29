<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfky40b8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfky40b8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:traffic-light-solid" /></template>
