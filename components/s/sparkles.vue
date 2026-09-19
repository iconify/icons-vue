<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot5pzvb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ot5pzvb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sparkles" /></template>
