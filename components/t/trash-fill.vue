<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa1h9pe-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fa1h9pe-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:trash-fill" /></template>
