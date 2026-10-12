<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa48vtf9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aa48vtf9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:toggle-left-filled" /></template>
