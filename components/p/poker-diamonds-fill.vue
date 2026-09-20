<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qenkhxbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qenkhxbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:poker-diamonds-fill" /></template>
