<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuv7dvbxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zuv7dvbxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:minus-small" /></template>
