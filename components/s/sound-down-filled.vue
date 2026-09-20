<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va3pi2mwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="va3pi2mwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:sound-down-filled" /></template>
