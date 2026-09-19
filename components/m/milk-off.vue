<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy9wulbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy9wulbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:milk-off" /></template>
