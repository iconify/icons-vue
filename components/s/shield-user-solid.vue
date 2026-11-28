<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmlr14bkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmlr14bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shield-user-solid" /></template>
