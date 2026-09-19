<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wflkaub9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wflkaub9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:zdf" /></template>
