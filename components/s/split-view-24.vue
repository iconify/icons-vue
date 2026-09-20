<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-1u-rbkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-1u-rbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:split-view-24" /></template>
