<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcqm4ebmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcqm4ebmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shop-sign" /></template>
