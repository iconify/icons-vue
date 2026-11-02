<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgn5mabhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgn5mabhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:trouser-fill" /></template>
