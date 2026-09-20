<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io1kddccq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io1kddccq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:trac" /></template>
