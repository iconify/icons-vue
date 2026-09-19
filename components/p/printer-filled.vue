<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btgo_69aw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btgo_69aw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:printer-filled" /></template>
