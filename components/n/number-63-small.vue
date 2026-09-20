<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka1pqbc-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ka1pqbc-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-63-small" /></template>
