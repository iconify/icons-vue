<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbnqgjsjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbnqgjsjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:opentofu" /></template>
