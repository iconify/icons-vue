<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aotw5p_wz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aotw5p_wz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:train-front-filled" /></template>
