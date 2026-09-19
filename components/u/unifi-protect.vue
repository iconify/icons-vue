<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgd3znb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgd3znb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:unifi-protect" /></template>
