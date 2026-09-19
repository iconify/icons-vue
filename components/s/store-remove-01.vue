<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2yml2zvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2yml2zvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:store-remove-01" /></template>
