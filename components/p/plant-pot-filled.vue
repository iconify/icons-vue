<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta53_k63o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ta53_k63o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:plant-pot-filled" /></template>
