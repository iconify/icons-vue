<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn_zpj-6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kn_zpj-6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:rainbow" /></template>
