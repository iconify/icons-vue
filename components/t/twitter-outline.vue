<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw4ipkbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rw4ipkbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:twitter-outline" /></template>
