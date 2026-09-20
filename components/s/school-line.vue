<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln0tm3pou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ln0tm3pou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:school-line" /></template>
