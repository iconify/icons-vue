<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvq6x6b8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvq6x6b8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:singlestore" /></template>
