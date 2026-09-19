<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/effyh-lne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="effyh-lne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:phone-x-mark" /></template>
