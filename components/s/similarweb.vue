<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu_iv8bix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hu_iv8bix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:similarweb" /></template>
