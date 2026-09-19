<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytg75cb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytg75cb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nbc" /></template>
