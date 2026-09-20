<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asz9aeb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asz9aeb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:microwave-off" /></template>
