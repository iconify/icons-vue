<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7nlxvbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="w7nlxvbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:user-group" /></template>
