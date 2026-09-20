<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhjnutkmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhjnutkmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:store-2-line" /></template>
