<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjkjpxb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjkjpxb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:thunder" /></template>
