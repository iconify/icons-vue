<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpv0g5b1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpv0g5b1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:trash" /></template>
