<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aeyq-vbow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aeyq-vbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:rewind-filled" /></template>
