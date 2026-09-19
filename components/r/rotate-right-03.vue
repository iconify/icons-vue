<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqapnsbfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqapnsbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rotate-right-03" /></template>
