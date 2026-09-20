<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxe83dlex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxe83dlex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:share-forward-box-line" /></template>
