<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd-wl6bnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nd-wl6bnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tune-vertical-alt" /></template>
