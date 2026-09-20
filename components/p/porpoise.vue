<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bztxhr94v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bztxhr94v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:porpoise" /></template>
