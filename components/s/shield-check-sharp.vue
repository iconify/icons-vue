<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw3w5nb6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nw3w5nb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shield-check-sharp" /></template>
