<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re784hbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re784hbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:salt" /></template>
