<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs7bsbb_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fs7bsbb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:phone-plus-fill" /></template>
