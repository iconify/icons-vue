<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbk-xc15w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbk-xc15w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rotate-right-06" /></template>
