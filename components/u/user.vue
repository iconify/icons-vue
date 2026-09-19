<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unwx_ab4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="unwx_ab4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:user" /></template>
