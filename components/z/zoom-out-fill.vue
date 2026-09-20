<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7v6w9b9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7v6w9b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:zoom-out-fill" /></template>
