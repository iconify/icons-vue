<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5c5v29kw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5c5v29kw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:swipe-up-04" /></template>
