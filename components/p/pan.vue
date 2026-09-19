<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwop6eh_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwop6eh_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:pan" /></template>
