<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic1z0ouap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ic1z0ouap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:rei" /></template>
