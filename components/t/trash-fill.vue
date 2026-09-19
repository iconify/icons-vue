<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfv6q6btr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfv6q6btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:trash-fill" /></template>
