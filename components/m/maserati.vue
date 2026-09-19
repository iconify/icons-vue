<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsjiht7-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsjiht7-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:maserati" /></template>
