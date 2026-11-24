<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7l97obbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o7l97obbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:radius-filled" /></template>
