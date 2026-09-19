<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i82ymobjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":536,"height":512};
const content = `<path class="i82ymobjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:star-half-alt" /></template>
