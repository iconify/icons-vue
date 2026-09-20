<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fan5bvbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fan5bvbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:wifi-alert-attention" /></template>
