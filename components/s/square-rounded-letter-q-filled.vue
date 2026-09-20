<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4pxx0bpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4pxx0bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-letter-q-filled" /></template>
