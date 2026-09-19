<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf_8c0wnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tf_8c0wnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:medal" /></template>
