<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnw47wb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnw47wb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:navigation-off-filled" /></template>
