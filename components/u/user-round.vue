<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnijyo0-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnijyo0-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:user-round" /></template>
