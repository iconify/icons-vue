<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xou0auhqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xou0auhqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:phone-forward" /></template>
