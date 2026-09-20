<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm04_4b2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm04_4b2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:search-24" /></template>
