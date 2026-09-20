<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upkp3hbxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upkp3hbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:slack" /></template>
