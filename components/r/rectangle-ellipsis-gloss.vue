<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y91mkccyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y91mkccyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rectangle-ellipsis-gloss" /></template>
