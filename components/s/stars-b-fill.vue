<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptvfbt_un.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptvfbt_un"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:stars-b-fill" /></template>
