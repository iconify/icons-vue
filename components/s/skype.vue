<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh0or-_jc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xh0or-_jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:skype" /></template>
