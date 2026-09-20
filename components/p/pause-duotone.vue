<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4rdbzh3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4rdbzh3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pause-duotone" /></template>
