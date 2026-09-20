<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noolj8nel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="noolj8nel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:phone-5" /></template>
