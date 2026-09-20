<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfu70ff8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfu70ff8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rows-4-line" /></template>
