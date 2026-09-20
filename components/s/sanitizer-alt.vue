<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez11qmbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ez11qmbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:sanitizer-alt" /></template>
