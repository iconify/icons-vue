<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr9zrtbsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kr9zrtbsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:right-arrow" /></template>
