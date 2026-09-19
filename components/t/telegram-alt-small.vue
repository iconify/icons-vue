<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da160bb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="da160bb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:telegram-alt-small" /></template>
