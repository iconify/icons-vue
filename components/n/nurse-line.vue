<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agc4itbdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agc4itbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:nurse-line" /></template>
