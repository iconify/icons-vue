<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc6x9foxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wc6x9foxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:messenger-fill" /></template>
