<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh3rw9bca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zh3rw9bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:moon-outline" /></template>
