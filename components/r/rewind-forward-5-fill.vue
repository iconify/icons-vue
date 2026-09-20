<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nunlv_k3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nunlv_k3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-forward-5-fill" /></template>
