<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtg9cxbjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vtg9cxbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:paperclip" /></template>
