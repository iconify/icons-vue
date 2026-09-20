<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lusqu___b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lusqu___b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:podium" /></template>
