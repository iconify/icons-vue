<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd9xa4bgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wd9xa4bgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:plus-circle" /></template>
