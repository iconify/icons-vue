<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r--g3ebmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r--g3ebmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:message-circle-dashed-check" /></template>
