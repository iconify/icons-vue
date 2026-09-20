<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-txgij0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-txgij0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:turn-up-right" /></template>
