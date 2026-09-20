<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmn6vv7gz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmn6vv7gz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:mention-24" /></template>
