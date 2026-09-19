<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvmey9bkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvmey9bkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:text-align-justified" /></template>
