<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlty2oa0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qlty2oa0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:mobile-android-alt" /></template>
