<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr4w21ckn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lr4w21ckn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pic-fill" /></template>
