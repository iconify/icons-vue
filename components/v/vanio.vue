<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yitxoybmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yitxoybmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:vanio" /></template>
