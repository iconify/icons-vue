<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_yxvjbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w_yxvjbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:telescope-filled" /></template>
