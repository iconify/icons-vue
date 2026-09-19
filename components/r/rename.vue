<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws0ombcdd.css';
import '../../css/t/t72impnyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ws0ombcdd"/><path class="t72impnyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:rename" /></template>
