<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svetj300y.css';
import '../../css/g/gwn0owbnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svetj300y"/><path class="gwn0owbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:user-voice" /></template>
