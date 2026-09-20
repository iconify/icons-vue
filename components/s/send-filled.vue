<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m35w55bsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m35w55bsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:send-filled" /></template>
