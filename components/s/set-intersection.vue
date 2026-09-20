<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk3vlyqac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk3vlyqac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:set-intersection" /></template>
