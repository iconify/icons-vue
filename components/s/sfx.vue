<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g21u-c7gh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g21u-c7gh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:sfx" /></template>
