<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_1qh8v2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_1qh8v2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-letter-i-filled" /></template>
