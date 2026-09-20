<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp9136o6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pp9136o6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:setting2-filled" /></template>
