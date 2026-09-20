<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb09m4xda.css';
import '../../css/g/gra6cwz6v.css';
import '../../css/y/yp1_ldbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tb09m4xda"/><path class="gra6cwz6v"/><path class="yp1_ldbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:sound-high-filled" /></template>
