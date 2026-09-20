<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef7crqbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ef7crqbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-alt-arrow-right-outline" /></template>
