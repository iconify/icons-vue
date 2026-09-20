<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x82e92b6s.css';
import '../../css/u/ubp77pb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x82e92b6s"/><path class="ubp77pb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pla" /></template>
