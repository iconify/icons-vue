<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j90eycc1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j90eycc1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:store" /></template>
