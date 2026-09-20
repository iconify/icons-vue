<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxi6jtjqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxi6jtjqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sunflower-line" /></template>
