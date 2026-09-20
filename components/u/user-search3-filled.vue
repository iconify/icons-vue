<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twrymnbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twrymnbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-search3-filled" /></template>
