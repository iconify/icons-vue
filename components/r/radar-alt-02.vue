<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w58vlgbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w58vlgbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:radar-alt-02" /></template>
