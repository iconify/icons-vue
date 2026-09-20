<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-n5hnboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-n5hnboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:store-edit-outline" /></template>
