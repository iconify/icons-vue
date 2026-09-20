<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gi8c8mbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gi8c8mbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-letter-p-filled" /></template>
