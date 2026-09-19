<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_94i1bvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x_94i1bvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:proxy-filled" /></template>
