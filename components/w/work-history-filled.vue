<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv1-qn0hn.css';
import '../../css/e/ezy_p22ip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vv1-qn0hn"/><path class="ezy_p22ip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:work-history-filled" /></template>
