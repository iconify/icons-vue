<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1gvs0ovj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1gvs0ovj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:send-horizontal-filled" /></template>
