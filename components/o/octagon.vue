<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4s6s33fq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4s6s33fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:octagon" /></template>
