<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebwb_ofxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebwb_ofxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:notification" /></template>
