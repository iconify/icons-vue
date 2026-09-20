<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itsabwu7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itsabwu7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:user-business-filled" /></template>
