<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osdr6bbou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osdr6bbou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:team-meeting-bold" /></template>
