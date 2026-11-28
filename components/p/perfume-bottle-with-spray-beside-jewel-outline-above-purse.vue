<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo8k2rb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jo8k2rb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:perfume-bottle-with-spray-beside-jewel-outline-above-purse" /></template>
