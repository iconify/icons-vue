<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvpw6c4jp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvpw6c4jp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:record-mail-fill" /></template>
