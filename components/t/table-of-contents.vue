<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk0od7ber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kk0od7ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:table-of-contents" /></template>
