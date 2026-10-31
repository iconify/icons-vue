<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/w/waw7qsjhy.css';
import '../../css/w/w_3kc9fcd.css';
import '../../css/c/c00_5pbek.css';
import '../../css/f/fi_e0dgpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="waw7qsjhy wm-shadow"/><path class="w_3kc9fcd wm-shadow"/><path class="c00_5pbek"/><path class="fi_e0dgpm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:star" /></template>
