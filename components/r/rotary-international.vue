<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgfgw121s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgfgw121s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:rotary-international" /></template>
