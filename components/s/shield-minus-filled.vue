<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb3r7vl8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pb3r7vl8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:shield-minus-filled" /></template>
