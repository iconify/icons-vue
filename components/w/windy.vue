<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prs0t9bmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prs0t9bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:windy" /></template>
