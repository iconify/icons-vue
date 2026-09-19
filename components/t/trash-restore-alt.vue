<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmgly0bog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="gmgly0bog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:trash-restore-alt" /></template>
