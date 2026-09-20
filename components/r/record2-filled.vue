<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm4a5uuyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nm4a5uuyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:record2-filled" /></template>
