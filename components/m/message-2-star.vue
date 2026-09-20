<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvw9ldb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvw9ldb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-2-star" /></template>
