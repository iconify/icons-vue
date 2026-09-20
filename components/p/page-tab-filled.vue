<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh13jvbja.css';
import '../../css/m/mdi0c_bip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jh13jvbja"/><path class="mdi0c_bip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:page-tab-filled" /></template>
