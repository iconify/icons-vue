<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opg4asb0t.css';
import '../../css/l/lrijolbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opg4asb0t"/><path class="lrijolbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:user-clock-light" /></template>
