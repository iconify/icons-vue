<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9b945bdq.css';
import '../../css/n/n3pztie1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9b945bdq"/><path class="n3pztie1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:play-circle-fill" /></template>
