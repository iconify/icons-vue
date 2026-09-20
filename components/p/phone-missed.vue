<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkhuum60o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkhuum60o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:phone-missed" /></template>
