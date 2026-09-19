<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le8ab_e8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="le8ab_e8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:menu-alt-2" /></template>
