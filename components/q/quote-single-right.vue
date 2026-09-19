<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at9wev70d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="at9wev70d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:quote-single-right" /></template>
