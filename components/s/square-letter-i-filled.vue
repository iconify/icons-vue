<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-xxpzbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g-xxpzbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-letter-i-filled" /></template>
