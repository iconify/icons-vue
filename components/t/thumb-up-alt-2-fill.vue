<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_ulnzfce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_ulnzfce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:thumb-up-alt-2-fill" /></template>
