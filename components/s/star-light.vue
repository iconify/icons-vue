<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1y9ezhsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1y9ezhsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:star-light" /></template>
