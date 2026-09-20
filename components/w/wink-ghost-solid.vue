<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8uofwzqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8uofwzqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:wink-ghost-solid" /></template>
