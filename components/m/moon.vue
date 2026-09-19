<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9r5umzcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9r5umzcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:moon" /></template>
