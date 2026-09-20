<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwzz-9b9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwzz-9b9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:subtitle-filled" /></template>
