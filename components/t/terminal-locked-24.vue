<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbl7r9mon.css';
import '../../css/z/zvcrm1bfj.css';
import '../../css/g/g5vtw-iho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="kbl7r9mon"/><path class="zvcrm1bfj"/><path class="g5vtw-iho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:terminal-locked-24" /></template>
