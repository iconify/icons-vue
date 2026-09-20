<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuucq2hxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iuucq2hxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:vala" /></template>
