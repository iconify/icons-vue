<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz17-3m3v.css';
import '../../css/q/q3_f8s1ue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gz17-3m3v"/><path class="q3_f8s1ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:task-double-filled" /></template>
