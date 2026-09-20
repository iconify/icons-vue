<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grg7xwilx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grg7xwilx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:profile-fill" /></template>
