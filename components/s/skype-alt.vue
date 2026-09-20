<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txxcw59-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txxcw59-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:skype-alt" /></template>
