<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ade6m6cnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ade6m6cnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:parasol-filled" /></template>
