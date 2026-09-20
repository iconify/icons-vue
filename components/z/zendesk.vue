<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wml9zxi4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wml9zxi4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:zendesk" /></template>
