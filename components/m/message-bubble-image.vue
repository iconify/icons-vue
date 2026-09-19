<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5v5asbue.css';
import '../../css/z/zbxahybdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5v5asbue"/><path class="zbxahybdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-bubble-image" /></template>
