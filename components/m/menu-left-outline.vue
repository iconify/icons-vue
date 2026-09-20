<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb7aw7omu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nb7aw7omu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:menu-left-outline" /></template>
