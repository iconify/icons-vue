<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie7tk9bnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ie7tk9bnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:rectangle-on-rectangle-angled" /></template>
