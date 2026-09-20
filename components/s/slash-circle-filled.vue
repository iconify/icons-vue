<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo5247bgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lo5247bgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:slash-circle-filled" /></template>
