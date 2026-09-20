<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvynadbvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvynadbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:turn-up-left" /></template>
