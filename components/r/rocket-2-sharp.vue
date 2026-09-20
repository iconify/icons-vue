<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir0t33bvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ir0t33bvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rocket-2-sharp" /></template>
