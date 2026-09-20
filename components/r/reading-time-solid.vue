<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uljtn5aar.css';
import '../../css/a/akh0cg09d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uljtn5aar"/><path clip-rule="evenodd" class="akh0cg09d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:reading-time-solid" /></template>
