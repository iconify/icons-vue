<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jycn4ccgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jycn4ccgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:sd" /></template>
