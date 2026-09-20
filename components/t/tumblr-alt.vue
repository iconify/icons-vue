<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxqzdbbny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxqzdbbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:tumblr-alt" /></template>
