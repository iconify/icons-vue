<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im-q8rvxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im-q8rvxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:stack-check" /></template>
