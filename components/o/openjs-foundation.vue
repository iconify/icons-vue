<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa32-bcua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa32-bcua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:openjs-foundation" /></template>
