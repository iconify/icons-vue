<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjhkzid7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjhkzid7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:skiing-snow-scooter-person" /></template>
