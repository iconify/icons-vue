<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy3z4m3dn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oy3z4m3dn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:volume-min-filled" /></template>
