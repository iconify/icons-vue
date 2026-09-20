<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyu0hzd1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyu0hzd1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mower-bag-on" /></template>
