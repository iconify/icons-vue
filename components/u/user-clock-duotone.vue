<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymayf7r7m.css';
import '../../css/o/ow15xdb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymayf7r7m"/><path class="ow15xdb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:user-clock-duotone" /></template>
