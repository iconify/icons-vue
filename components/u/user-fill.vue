<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-01dc-tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-01dc-tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-fill" /></template>
