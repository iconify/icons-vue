<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqq61kbnt.css';
import '../../css/t/tbcp7-bab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqq61kbnt"/><path class="tbcp7-bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:project-roadmap-24" /></template>
