<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7gi09b7p.css';
import '../../css/i/i93jdftas.css';
import '../../css/c/c6-sq8xgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7gi09b7p"/><path class="i93jdftas"/><path class="c6-sq8xgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:release-24" /></template>
