<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5ohcpp2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5ohcpp2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:package-filled" /></template>
