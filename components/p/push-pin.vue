<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y07zuubod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y07zuubod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:push-pin" /></template>
