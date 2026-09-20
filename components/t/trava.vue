<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jka59sbfy.css';
import '../../css/s/syimw_bzt.css';
import '../../css/y/yeqou0bji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jka59sbfy"/><path class="syimw_bzt"/><path class="yeqou0bji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:trava" /></template>
