<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8et9mopb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8et9mopb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:mountain" /></template>
