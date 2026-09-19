<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdk8pinup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="mdk8pinup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:vk" /></template>
