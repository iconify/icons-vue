<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p18owjbby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1027};
const content = `<path class="p18owjbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:refresh" /></template>
