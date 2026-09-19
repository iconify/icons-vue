<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jeipv6u4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jeipv6u4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:slash" /></template>
