<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja2z0ptxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ja2z0ptxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pound-sterling" /></template>
