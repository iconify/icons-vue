<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/watmo3bac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="watmo3bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:user-list-filled" /></template>
