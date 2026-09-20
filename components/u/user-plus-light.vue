<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s58yrv62u.css';
import '../../css/h/hkyycvtfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s58yrv62u"/><path class="hkyycvtfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:user-plus-light" /></template>
