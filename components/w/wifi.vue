<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrsk8i_6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrsk8i_6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:wifi" /></template>
