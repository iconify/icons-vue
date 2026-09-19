<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ain1iwb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ain1iwb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:virus-slash-filled" /></template>
