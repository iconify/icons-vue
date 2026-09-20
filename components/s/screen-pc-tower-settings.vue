<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a51uagbxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="a51uagbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:screen-pc-tower-settings" /></template>
