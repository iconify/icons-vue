<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8kduccib.css';
import '../../css/j/jr633_uxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8kduccib"/><path class="jr633_uxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:movr" /></template>
