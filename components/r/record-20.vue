<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd9t-4b_w.css';
import '../../css/v/vixdv7vsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pd9t-4b_w"/><path class="vixdv7vsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:record-20" /></template>
