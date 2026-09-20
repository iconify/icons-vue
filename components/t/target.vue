<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvzhpnn4z.css';
import '../../css/l/ljp4sfbmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvzhpnn4z"/><path class="ljp4sfbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:target" /></template>
