<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2w_dsb6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2w_dsb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:sparta" /></template>
