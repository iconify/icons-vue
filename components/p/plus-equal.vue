<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etikd70mi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etikd70mi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:plus-equal" /></template>
