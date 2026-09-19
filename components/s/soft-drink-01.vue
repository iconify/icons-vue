<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2m05ta2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2m05ta2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:soft-drink-01" /></template>
