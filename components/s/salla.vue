<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxzt0xb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxzt0xb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:salla" /></template>
