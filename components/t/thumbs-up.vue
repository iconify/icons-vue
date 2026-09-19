<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvllrb36k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvllrb36k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:thumbs-up" /></template>
