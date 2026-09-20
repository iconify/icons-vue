<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh6debbfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eh6debbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:puppet" /></template>
