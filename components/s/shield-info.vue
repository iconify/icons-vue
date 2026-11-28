<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6wjzsk-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6wjzsk-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:shield-info" /></template>
