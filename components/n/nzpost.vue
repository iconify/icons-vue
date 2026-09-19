<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcd9tq4hd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcd9tq4hd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nzpost" /></template>
