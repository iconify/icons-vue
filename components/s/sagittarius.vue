<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7f5qob6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7f5qob6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sagittarius" /></template>
