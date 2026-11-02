<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqbe3v_5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqbe3v_5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sandstorm-line" /></template>
