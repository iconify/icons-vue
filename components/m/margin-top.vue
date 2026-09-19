<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv-2dkxjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vv-2dkxjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:margin-top" /></template>
