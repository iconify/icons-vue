<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugvei2bjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugvei2bjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:stan" /></template>
