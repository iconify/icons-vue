<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj0w1_9qx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aj0w1_9qx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:moneybag-alt" /></template>
