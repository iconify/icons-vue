<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2pyozvqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2pyozvqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:settings-line" /></template>
