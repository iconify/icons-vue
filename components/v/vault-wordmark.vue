<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzn2jab7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="nzn2jab7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:vault-wordmark" /></template>
