<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz-ytj-jx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kz-ytj-jx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:mouse-pointer" /></template>
