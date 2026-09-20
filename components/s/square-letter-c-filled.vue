<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x270g9bed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x270g9bed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-letter-c-filled" /></template>
