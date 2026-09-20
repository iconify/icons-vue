<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbndu9beu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbndu9beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:recoil" /></template>
