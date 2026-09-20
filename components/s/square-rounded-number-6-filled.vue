<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc0uoabuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sc0uoabuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-number-6-filled" /></template>
