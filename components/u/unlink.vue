<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jci9iccjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jci9iccjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:unlink" /></template>
