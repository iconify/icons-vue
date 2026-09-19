<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p13ni4b9t.css';
import '../../css/n/n3vra2bpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p13ni4b9t"/><path class="n3vra2bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:news" /></template>
