<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-flpfq5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-flpfq5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:star-circle-fill" /></template>
