<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kki7enbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kki7enbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sparkles-solid" /></template>
