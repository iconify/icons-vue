<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3m2t7bds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p3m2t7bds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-letter-n-filled" /></template>
