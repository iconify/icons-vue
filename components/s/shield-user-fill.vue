<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xshb9nbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xshb9nbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shield-user-fill" /></template>
