<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln5b_cbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1027,"height":1026};
const content = `<path class="ln5b_cbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:rorschach" /></template>
