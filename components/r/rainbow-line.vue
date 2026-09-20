<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yarw-nzsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yarw-nzsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:rainbow-line" /></template>
