<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z64gnu31o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":24};
const content = `<path class="z64gnu31o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:mongodb" /></template>
