<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbtoxbc4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbtoxbc4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:vk" /></template>
