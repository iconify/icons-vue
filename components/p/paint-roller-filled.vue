<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv_oh1bhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gv_oh1bhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:paint-roller-filled" /></template>
