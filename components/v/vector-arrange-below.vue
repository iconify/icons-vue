<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tia1afx0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tia1afx0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vector-arrange-below" /></template>
