<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6rueab4y.css';
import '../../css/k/kcx9ch0qs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="e6rueab4y"/><path class="kcx9ch0qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:ukraine" /></template>
