<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw-ogieda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aw-ogieda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-pen-filled" /></template>
