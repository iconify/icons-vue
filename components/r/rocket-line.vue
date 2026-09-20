<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd-l39ban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zd-l39ban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:rocket-line" /></template>
