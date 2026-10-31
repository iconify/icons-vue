<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/r/rtny4kbqq.css';
import '../../css/s/ss0gbbcxt.css';
import '../../css/x/xih1z7baw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="rtny4kbqq wm-shadow"/><path class="ss0gbbcxt wm-shadow"/><path class="xih1z7baw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:snowflake" /></template>
