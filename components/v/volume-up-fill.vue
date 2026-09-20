<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xya1qabtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xya1qabtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:volume-up-fill" /></template>
