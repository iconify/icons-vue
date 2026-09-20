<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq6f6bcoa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kq6f6bcoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:required" /></template>
