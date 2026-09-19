<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am499lb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="am499lb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:radio-check" /></template>
