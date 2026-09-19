<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xih7reb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xih7reb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:steps" /></template>
