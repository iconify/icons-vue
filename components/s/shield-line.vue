<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvjom7b2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvjom7b2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:shield-line" /></template>
