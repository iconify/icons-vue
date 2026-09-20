<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk0zo2kay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk0zo2kay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:volume-mute-fill" /></template>
