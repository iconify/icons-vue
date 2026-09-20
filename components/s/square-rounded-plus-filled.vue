<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6ui85kay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6ui85kay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-plus-filled" /></template>
