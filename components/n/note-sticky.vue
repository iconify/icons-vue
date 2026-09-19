<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic2j-qb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ic2j-qb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:note-sticky" /></template>
