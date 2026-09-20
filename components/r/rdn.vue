<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xra98m7aa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xra98m7aa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:rdn" /></template>
