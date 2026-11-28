<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi51t6b3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bi51t6b3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:shield-half-check" /></template>
