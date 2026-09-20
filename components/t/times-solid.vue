<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcjq9ynkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcjq9ynkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:times-solid" /></template>
