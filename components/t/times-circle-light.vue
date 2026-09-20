<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7-64xb2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7-64xb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:times-circle-light" /></template>
