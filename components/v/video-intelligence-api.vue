<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfzc8lbfq.css';
import '../../css/s/si00v7b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfzc8lbfq"/><path class="si00v7b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:video-intelligence-api" /></template>
