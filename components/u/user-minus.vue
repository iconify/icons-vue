<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtpcm5jix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtpcm5jix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-minus" /></template>
