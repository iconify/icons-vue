<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elpxm65ap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="elpxm65ap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:settings-filled" /></template>
