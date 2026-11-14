<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efng8jwqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efng8jwqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:philippine-peso" /></template>
