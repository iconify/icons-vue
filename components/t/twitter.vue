<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnzj65beh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnzj65beh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:twitter" /></template>
