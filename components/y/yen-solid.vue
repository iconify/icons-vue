<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plxt9oube.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plxt9oube"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:yen-solid" /></template>
