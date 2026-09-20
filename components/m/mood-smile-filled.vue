<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc0lycc_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bc0lycc_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:mood-smile-filled" /></template>
