<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8l3c2xkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8l3c2xkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:transfer-left" /></template>
