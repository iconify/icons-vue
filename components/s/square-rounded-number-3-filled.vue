<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynah5zt6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynah5zt6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-number-3-filled" /></template>
