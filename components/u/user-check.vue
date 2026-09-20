<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wauk5sbqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wauk5sbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:user-check" /></template>
