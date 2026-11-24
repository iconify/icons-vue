<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a35m7db-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a35m7db-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:robot-arm-filled" /></template>
