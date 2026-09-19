<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6lmsxb0c.css';
import '../../css/t/thp3xzwhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6lmsxb0c"/><path class="thp3xzwhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:meat" /></template>
