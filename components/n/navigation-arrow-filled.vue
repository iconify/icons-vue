<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbdkh698b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbdkh698b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:navigation-arrow-filled" /></template>
