<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwae5qbdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwae5qbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:nxra" /></template>
