<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3gsr-bln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3gsr-bln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:user-up" /></template>
