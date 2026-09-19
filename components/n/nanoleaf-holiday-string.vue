<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a01f0rssn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a01f0rssn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nanoleaf-holiday-string" /></template>
