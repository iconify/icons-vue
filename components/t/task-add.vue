<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj8i9n62v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sj8i9n62v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:task-add" /></template>
