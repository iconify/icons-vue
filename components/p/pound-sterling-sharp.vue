<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqlzyghhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqlzyghhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pound-sterling-sharp" /></template>
