<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-29rqb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-29rqb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:message-square-plus" /></template>
