<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k54_jgbmz.css';
import '../../css/w/wwzneb9rp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k54_jgbmz"/><path class="wwzneb9rp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:usergroup-add-filled" /></template>
