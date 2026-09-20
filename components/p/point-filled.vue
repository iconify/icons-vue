<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo7ac-bbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qo7ac-bbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:point-filled" /></template>
