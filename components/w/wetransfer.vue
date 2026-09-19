<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgh3b7bsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgh3b7bsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:wetransfer" /></template>
