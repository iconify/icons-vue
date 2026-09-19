<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr92k7byi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nr92k7byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:triangle" /></template>
