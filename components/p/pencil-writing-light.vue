<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohmadlugj.css';
import '../../css/h/h89cyrqhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohmadlugj"/><path class="h89cyrqhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:pencil-writing-light" /></template>
