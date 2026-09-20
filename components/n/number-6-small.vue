<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea7lc5b7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea7lc5b7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-6-small" /></template>
