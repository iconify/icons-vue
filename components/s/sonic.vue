<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p49a8zbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p49a8zbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:sonic" /></template>
